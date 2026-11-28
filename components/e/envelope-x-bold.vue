<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcla7g79v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vcla7g79v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:envelope-x-bold" /></template>
