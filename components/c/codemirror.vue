<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh7rg0bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sh7rg0bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:codemirror" /></template>
