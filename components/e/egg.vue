<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epuliwv2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="epuliwv2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:egg" /></template>
