<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbvimpb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pbvimpb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:groovy" /></template>
