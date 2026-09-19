<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xla7vihkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xla7vihkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:folder-remove" /></template>
