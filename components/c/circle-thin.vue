<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdk6xlj0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="qdk6xlj0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:circle-thin" /></template>
