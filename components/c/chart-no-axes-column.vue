<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4wt8hb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4wt8hb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chart-no-axes-column" /></template>
