<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elfvk3b5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="elfvk3b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:l-square" /></template>
