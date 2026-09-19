<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yorjo8b9o.css';
import '../../css/s/sq7litb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yorjo8b9o"/><path class="sq7litb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:home-add" /></template>
