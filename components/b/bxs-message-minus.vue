<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_hn9_sif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_hn9_sif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-minus" /></template>
