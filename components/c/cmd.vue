<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq367fyro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="rq367fyro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cmd" /></template>
