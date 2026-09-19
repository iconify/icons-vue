<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-9ay8bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o-9ay8bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:knot" /></template>
