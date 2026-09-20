<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn_0d_bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn_0d_bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-plus" /></template>
