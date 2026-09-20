<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q45pn-bge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q45pn-bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:dropbox" /></template>
