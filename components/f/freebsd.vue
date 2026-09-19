<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwbszgk6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kwbszgk6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:freebsd" /></template>
