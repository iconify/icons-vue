<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1f2w4bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1f2w4bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:club-solid" /></template>
