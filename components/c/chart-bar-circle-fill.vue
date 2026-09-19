<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyl2f4kmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="vyl2f4kmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chart-bar-circle-fill" /></template>
