<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpe4mlbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tpe4mlbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:document-reference" /></template>
