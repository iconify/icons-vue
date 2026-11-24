<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_8ytmbdv.css';
import '../../css/n/nicoetbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_8ytmbdv"/><path class="nicoetbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:chart-pie-filled" /></template>
