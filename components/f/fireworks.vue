<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwb0-zpbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwb0-zpbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:fireworks" /></template>
