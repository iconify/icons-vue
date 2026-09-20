<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb13_846r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb13_846r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-g-circle" /></template>
