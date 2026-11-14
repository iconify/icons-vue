<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_c_e_bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_c_e_bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-chemistry-02" /></template>
