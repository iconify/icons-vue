<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhw8cnbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="yhw8cnbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:heart-on-fire" /></template>
