<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9suhacgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="x9suhacgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:gradient" /></template>
