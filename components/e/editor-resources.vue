<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq57xzbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sq57xzbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:editor-resources" /></template>
