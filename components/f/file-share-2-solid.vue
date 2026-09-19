<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjroy5biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="hjroy5biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:file-share-2-solid" /></template>
