<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f045yabin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f045yabin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:gavel" /></template>
