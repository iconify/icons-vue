<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgt9i3n5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mgt9i3n5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:error" /></template>
