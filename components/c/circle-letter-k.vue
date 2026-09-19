<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7r2ne1tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r7r2ne1tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-letter-k" /></template>
