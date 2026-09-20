<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1d82tqjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1d82tqjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-x" /></template>
