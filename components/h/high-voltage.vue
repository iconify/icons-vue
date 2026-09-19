<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy42rxa0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qy42rxa0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:high-voltage" /></template>
