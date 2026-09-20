<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfcjx_esq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfcjx_esq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-off" /></template>
