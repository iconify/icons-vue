<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_z58cbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_z58cbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-big-up-lines-filled" /></template>
