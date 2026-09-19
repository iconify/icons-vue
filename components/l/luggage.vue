<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie82q_bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie82q_bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:luggage" /></template>
