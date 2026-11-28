<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9539sb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9539sb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:clipboard-solid" /></template>
