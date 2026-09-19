<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqkk9sb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vqkk9sb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:download" /></template>
