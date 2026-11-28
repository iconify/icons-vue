<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6-z5cb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6-z5cb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file" /></template>
