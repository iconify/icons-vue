<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/powe5iexb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="powe5iexb primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:crop-duotone" /></template>
