<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsi0siggj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vsi0siggj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:ghost" /></template>
