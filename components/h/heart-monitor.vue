<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo2ouibij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="yo2ouibij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:heart-monitor" /></template>
