<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e09bccccb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e09bccccb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:file-wizard" /></template>
