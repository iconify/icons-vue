<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2_x_fx_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2_x_fx_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:credit-card" /></template>
