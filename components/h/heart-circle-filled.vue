<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul0z0lfqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul0z0lfqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:heart-circle-filled" /></template>
