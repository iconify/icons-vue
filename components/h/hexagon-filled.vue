<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihud3xmus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihud3xmus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-filled" /></template>
