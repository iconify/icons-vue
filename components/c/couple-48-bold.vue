<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjm0c5bzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bjm0c5bzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:couple-48-bold" /></template>
