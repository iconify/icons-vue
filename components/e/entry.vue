<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn-robb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn-robb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:entry" /></template>
