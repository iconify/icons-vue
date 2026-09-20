<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_whbcc0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h_whbcc0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:digital-totem-with-wifi" /></template>
