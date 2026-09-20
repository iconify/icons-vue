<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilnq8gpil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ilnq8gpil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:border-all" /></template>
