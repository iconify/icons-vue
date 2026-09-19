<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3ggxmb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="w3ggxmb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:comment" /></template>
