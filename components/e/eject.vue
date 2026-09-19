<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmj_l2fxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmj_l2fxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:eject" /></template>
