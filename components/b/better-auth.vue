<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1s_e0b7s.css';
import '../../css/c/cvuri1beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1s_e0b7s"/><path class="cvuri1beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:better-auth" /></template>
