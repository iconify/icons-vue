<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grn2m8dbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="grn2m8dbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:archive-box" /></template>
