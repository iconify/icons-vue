<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9a3omb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="z9a3omb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:lineicons-symbol" /></template>
