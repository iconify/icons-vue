<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzs052bzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1022,"height":1024};
const content = `<path class="bzs052bzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:dog" /></template>
