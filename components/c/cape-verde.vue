<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c85pd_b_f.css';
import '../../css/m/mu9as98bc.css';
import '../../css/m/mpcblwabv.css';
import '../../css/u/u5qijbbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="c85pd_b_f"/><path class="mu9as98bc"/><path class="mpcblwabv"/><path class="u5qijbbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:cape-verde" /></template>
