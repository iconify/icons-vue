<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ieszopq_p.css';
import '../../css/u/ua2r80buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ieszopq_p"/><path class="ua2r80buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-rain-wind-filled" /></template>
