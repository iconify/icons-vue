<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1hce7bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z1hce7bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:clipboard" /></template>
