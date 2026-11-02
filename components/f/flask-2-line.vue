<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zup424bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zup424bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flask-2-line" /></template>
