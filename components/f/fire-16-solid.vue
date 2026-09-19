<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcwpt2h2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mcwpt2h2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:fire-16-solid" /></template>
