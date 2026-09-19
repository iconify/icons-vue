<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf8ifdctz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1760,"height":1760};
const content = `<path class="mf8ifdctz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:gavel" /></template>
