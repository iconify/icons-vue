<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tys5xt2qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tys5xt2qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cursor-target-1" /></template>
