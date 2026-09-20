<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydlfnzits.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydlfnzits"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:amazonluna" /></template>
