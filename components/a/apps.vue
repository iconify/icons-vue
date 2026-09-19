<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6j-j1bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":472};
const content = `<path class="t6j-j1bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:apps" /></template>
