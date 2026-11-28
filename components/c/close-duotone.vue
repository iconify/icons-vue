<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-78cp69d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-78cp69d primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:close-duotone" /></template>
