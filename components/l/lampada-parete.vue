<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erj_vhb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erj_vhb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lampada-parete" /></template>
