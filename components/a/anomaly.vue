<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaoe0hbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zaoe0hbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:anomaly" /></template>
