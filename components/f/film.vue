<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0t9246lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z0t9246lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:film" /></template>
