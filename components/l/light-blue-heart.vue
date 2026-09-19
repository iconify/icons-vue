<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df9m2wbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="df9m2wbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:light-blue-heart" /></template>
