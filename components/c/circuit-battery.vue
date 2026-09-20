<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvu_a7hvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvu_a7hvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circuit-battery" /></template>
