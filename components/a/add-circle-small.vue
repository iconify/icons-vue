<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf3jhqdyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bf3jhqdyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:add-circle-small" /></template>
