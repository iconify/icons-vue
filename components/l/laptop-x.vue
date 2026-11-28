<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g66f04s7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g66f04s7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:laptop-x" /></template>
