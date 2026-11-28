<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md_acy2pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md_acy2pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clock-play" /></template>
