<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw-g8b8iq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aw-g8b8iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:edit" /></template>
