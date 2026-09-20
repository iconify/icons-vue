<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9xqpqhsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w9xqpqhsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bus-within-guideway" /></template>
