<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5gvgqbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k5gvgqbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:container-fill" /></template>
