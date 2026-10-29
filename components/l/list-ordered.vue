<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfycjybkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfycjybkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:list-ordered" /></template>
