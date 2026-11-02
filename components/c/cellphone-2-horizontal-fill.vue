<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoqgnebgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoqgnebgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cellphone-2-horizontal-fill" /></template>
