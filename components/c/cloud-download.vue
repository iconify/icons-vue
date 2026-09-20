<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-6jwippj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a-6jwippj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:cloud-download" /></template>
