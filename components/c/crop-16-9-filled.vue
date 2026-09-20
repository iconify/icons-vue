<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rns8vj0tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rns8vj0tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:crop-16-9-filled" /></template>
