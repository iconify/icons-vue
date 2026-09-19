<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flue7eb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="flue7eb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:grunt" /></template>
