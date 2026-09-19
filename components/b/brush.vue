<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d058umb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="d058umb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:brush" /></template>
