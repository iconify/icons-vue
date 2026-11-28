<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_g3i6r_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_g3i6r_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-up-solid" /></template>
