<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqsm07bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uqsm07bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ioke" /></template>
