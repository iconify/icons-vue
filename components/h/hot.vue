<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud5lazbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":819,"height":750};
const content = `<path class="ud5lazbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:hot" /></template>
