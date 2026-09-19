<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa2bmhb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wa2bmhb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:axe" /></template>
