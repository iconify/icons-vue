<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apd_cdc3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="apd_cdc3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:format-italic" /></template>
