<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw_q1lu_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw_q1lu_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:code" /></template>
