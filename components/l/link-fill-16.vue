<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgu2-5bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xgu2-5bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:link-fill-16" /></template>
