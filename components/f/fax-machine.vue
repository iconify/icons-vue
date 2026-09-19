<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni46c40-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ni46c40-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:fax-machine" /></template>
