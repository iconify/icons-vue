<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia9t81bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia9t81bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:infinite" /></template>
