<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsf-4ub0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zsf-4ub0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-big-down-lines-filled" /></template>
