<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqpf2n-tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="aqpf2n-tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:circle" /></template>
