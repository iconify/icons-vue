<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xac6b2u_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xac6b2u_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:antenna-bars-off" /></template>
