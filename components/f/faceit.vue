<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xep8ytzzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xep8ytzzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:faceit" /></template>
