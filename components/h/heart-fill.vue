<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c294zkb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="c294zkb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:heart-fill" /></template>
