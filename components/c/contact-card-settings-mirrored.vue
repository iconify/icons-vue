<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og1xdifdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="og1xdifdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:contact-card-settings-mirrored" /></template>
