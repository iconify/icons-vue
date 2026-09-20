<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoy593b6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoy593b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mail-certified-outline" /></template>
