<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpavm-beg.css';
import '../../css/p/pfluh_2pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpavm-beg"/><path clip-rule="evenodd" class="pfluh_2pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:home-outline" /></template>
