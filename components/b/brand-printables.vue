<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd9zdhbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd9zdhbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-printables" /></template>
