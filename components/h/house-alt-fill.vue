<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usx9ajksc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="usx9ajksc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:house-alt-fill" /></template>
