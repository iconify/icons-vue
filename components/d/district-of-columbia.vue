<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw-m6vb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yw-m6vb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:district-of-columbia" /></template>
