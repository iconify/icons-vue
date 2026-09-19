<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ariq7rbyx.css';
import '../../css/r/r8qtg0eea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ariq7rbyx"/><path class="r8qtg0eea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:customer" /></template>
