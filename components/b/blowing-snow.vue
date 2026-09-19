<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwsuywb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bwsuywb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:blowing-snow" /></template>
