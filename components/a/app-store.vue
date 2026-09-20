<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7j9fnbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g7j9fnbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:app-store" /></template>
