<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf4pigb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf4pigb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:guardian" /></template>
