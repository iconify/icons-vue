<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0c4xobxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="k0c4xobxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:earth-asia-o" /></template>
