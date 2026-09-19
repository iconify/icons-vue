<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_4z2nb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_4z2nb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-rewind-circle" /></template>
