<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/keo_ub1ao.css';
import '../../css/m/mrxynabnu.css';
import '../../css/v/vgjcg77tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="keo_ub1ao"/><path class="mrxynabnu"/><path class="vgjcg77tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docspell" /></template>
