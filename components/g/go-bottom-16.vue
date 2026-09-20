<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp8-qrb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gp8-qrb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:go-bottom-16" /></template>
