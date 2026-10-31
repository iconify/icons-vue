<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x25h2u90g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x25h2u90g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:letter-w" /></template>
