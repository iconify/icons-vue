<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-3d54bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="a-3d54bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:heliport-14" /></template>
