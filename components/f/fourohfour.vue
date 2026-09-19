<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/due149pmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="due149pmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fourohfour" /></template>
