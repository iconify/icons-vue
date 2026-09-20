<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hji5n7yfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hji5n7yfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-sort-alt-1-line" /></template>
