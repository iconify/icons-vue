<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl0qf53pv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="fl0qf53pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:collection-small" /></template>
