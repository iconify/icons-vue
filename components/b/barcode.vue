<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3-u3ab7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="h3-u3ab7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:barcode" /></template>
