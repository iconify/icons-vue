<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqyidkdmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqyidkdmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:laptop-gear" /></template>
