<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynr-1ab1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynr-1ab1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:circle" /></template>
