<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o73n4sb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o73n4sb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:green-circle" /></template>
