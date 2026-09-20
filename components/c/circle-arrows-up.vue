<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co3xfgj9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="co3xfgj9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrows-up" /></template>
