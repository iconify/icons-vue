<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh1fr4b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qh1fr4b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:folder-open" /></template>
