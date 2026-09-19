<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahlge8buh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ahlge8buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:creative-commons" /></template>
