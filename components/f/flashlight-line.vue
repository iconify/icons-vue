<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljdxm2brp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljdxm2brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flashlight-line" /></template>
