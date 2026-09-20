<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmuh9obmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qmuh9obmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:circle-filled-16" /></template>
