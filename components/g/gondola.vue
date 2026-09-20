<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfg2ff-7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="lfg2ff-7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:gondola" /></template>
