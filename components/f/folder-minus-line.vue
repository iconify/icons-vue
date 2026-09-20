<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt-x7st9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt-x7st9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-minus-line" /></template>
