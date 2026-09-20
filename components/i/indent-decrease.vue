<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze8ppqcua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ze8ppqcua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:indent-decrease" /></template>
