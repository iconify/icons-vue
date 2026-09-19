<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_i561bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":26};
const content = `<path class="y_i561bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-26" /></template>
