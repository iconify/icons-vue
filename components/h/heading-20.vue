<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iydi5xvdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iydi5xvdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:heading-20" /></template>
