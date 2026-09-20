<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v32kf_bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v32kf_bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:carousel-horizontal-filled" /></template>
