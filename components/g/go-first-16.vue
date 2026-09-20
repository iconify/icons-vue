<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nin7w1fdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nin7w1fdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:go-first-16" /></template>
