<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgl4bwb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgl4bwb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:coin-rupee-filled" /></template>
