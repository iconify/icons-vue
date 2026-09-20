<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un4u_u6jm.css';
import '../../css/m/m0_43203z.css';
import '../../css/e/e-4rvpmbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un4u_u6jm"/><path class="m0_43203z"/><path class="e-4rvpmbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:layer-group" /></template>
