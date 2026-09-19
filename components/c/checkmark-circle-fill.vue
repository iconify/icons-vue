<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyj3p-b1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="pyj3p-b1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:checkmark-circle-fill" /></template>
