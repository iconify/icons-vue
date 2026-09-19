<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt9h82eme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kt9h82eme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:cmake" /></template>
