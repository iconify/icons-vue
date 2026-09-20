<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avq__8bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avq__8bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:code-xml-fill" /></template>
