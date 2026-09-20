<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woqf0obxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="woqf0obxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:hammer" /></template>
