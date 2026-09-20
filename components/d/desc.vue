<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9nl6fbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="x9nl6fbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:desc" /></template>
