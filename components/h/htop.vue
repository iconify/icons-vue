<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olr5yl-eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olr5yl-eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:htop" /></template>
