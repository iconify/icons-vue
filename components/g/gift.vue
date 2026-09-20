<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnj3ysbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tnj3ysbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:gift" /></template>
