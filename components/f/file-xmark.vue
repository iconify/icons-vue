<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbe3tm0cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qbe3tm0cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:file-xmark" /></template>
