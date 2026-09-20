<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnfhveh-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="qnfhveh-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:angle-left" /></template>
