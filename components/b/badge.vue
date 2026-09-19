<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvwox8bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uvwox8bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:badge" /></template>
