<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh1y5yg1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh1y5yg1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:adobedreamweaver" /></template>
