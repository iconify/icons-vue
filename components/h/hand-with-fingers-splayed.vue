<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akm_f5a5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="akm_f5a5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:hand-with-fingers-splayed" /></template>
