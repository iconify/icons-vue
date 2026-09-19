<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc1-cb1mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc1-cb1mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:caret-circle-down" /></template>
