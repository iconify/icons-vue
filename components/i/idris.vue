<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmwr7vi-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":279,"height":512};
const content = `<path class="kmwr7vi-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:idris" /></template>
