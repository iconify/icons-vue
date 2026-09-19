<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auhox3b4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auhox3b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:code" /></template>
