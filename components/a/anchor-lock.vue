<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln4fjcylo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ln4fjcylo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:anchor-lock" /></template>
