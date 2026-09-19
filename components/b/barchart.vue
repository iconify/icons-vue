<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy2302llc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dy2302llc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:barchart" /></template>
