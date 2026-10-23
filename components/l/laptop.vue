<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jljngzhrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jljngzhrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:laptop" /></template>
