<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft7132ikh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ft7132ikh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:document-report" /></template>
