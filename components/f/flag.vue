<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6k2484ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="b6k2484ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:flag" /></template>
