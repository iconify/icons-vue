<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_hrlfu3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_hrlfu3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:coin-euro-filled" /></template>
