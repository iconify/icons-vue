<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivwl1-arg.css';
import '../../css/u/uj46r2dkm.css';
import '../../css/m/m_u9wub5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivwl1-arg"/><path class="uj46r2dkm"/><path class="m_u9wub5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:car-bolt" /></template>
