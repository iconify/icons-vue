<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7s-ezb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7s-ezb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circles-alt-filled" /></template>
