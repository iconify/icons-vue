<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au2_5bcul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="au2_5bcul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:envelope" /></template>
