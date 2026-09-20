<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-s5j9brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-s5j9brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-check" /></template>
