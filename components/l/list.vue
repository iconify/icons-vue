<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhla8kavv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhla8kavv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:list" /></template>
