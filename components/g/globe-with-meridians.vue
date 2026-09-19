<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9gu4yi6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s9gu4yi6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:globe-with-meridians" /></template>
