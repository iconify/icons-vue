<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byjpmcj3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":280,"height":448};
const content = `<path class="byjpmcj3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:egg" /></template>
