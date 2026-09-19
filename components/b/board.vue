<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6ijw0v2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q6ijw0v2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:board" /></template>
