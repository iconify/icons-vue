<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wopdurd2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wopdurd2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-top-left-alt-filled" /></template>
