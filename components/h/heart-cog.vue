<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwff-u_lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwff-u_lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:heart-cog" /></template>
