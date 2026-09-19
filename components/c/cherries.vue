<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8skwtbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="q8skwtbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:cherries" /></template>
