<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfgm4ibzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b gfgm4ibzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:apps-alt-filled" /></template>
