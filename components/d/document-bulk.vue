<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-8chbcru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j-8chbcru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:document-bulk" /></template>
