<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zko-cjbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zko-cjbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bomb-line" /></template>
