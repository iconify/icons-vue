<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojqan9b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ojqan9b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-printer-outline" /></template>
