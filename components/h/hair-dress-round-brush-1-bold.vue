<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sztuft7up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sztuft7up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:hair-dress-round-brush-1-bold" /></template>
