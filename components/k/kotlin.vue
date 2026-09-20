<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbjcdoj4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbjcdoj4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:kotlin" /></template>
