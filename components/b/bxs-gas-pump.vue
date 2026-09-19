<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stm_q-k-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stm_q-k-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-gas-pump" /></template>
