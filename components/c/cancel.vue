<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb3n1kb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hb3n1kb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:cancel" /></template>
