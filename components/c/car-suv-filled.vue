<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgao2r20j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgao2r20j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:car-suv-filled" /></template>
