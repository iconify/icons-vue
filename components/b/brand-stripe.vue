<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtv_b7_ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtv_b7_ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-stripe" /></template>
