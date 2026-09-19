<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6d4qmufc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="x6d4qmufc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:gauge-badge-plus" /></template>
