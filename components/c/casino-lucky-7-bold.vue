<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfsrp3blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfsrp3blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:casino-lucky-7-bold" /></template>
