<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwjefd-_m.css';
import '../../css/m/mwa49fbjg.css';
import '../../css/u/uj2eeb6wg.css';
import '../../css/r/rk8d_ibcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwjefd-_m"/><path clip-rule="evenodd" class="mwa49fbjg"/><path class="uj2eeb6wg"/><path clip-rule="evenodd" class="rk8d_ibcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:id-card" /></template>
