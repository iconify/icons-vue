<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9d093afe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="a9d093afe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hierarchy-4" /></template>
