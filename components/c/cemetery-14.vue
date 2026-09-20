<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bji8e2b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="bji8e2b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:cemetery-14" /></template>
