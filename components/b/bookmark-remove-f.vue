<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5m-knbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-1.5};
const content = `<path class="f5m-knbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:bookmark-remove-f" /></template>
