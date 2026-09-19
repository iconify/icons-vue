<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dte1lf23o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="dte1lf23o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:camping" /></template>
