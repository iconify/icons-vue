<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfd7l7bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="dfd7l7bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:link" /></template>
