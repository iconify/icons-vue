<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akli7jbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="akli7jbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:caret-solid-right" /></template>
