<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfqk1vksr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path clip-rule="evenodd" class="xfqk1vksr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:logo-reaper" /></template>
