<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khx4plw-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khx4plw-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hiking-line" /></template>
