<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laa1tab1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="laa1tab1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bean" /></template>
