<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp3xq4blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp3xq4blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:drive-safety" /></template>
