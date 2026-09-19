<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgb26qb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgb26qb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:facebook-circle" /></template>
