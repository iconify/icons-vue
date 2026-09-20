<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etuvs-83s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="etuvs-83s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-button-to-top-arrow-up-line-to-top" /></template>
