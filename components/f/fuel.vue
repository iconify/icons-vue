<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue_vn6bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ue_vn6bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:fuel" /></template>
