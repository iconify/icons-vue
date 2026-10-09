<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wznngcc3g.css';
import '../../css/t/tk3p5zjbs.css';
import '../../css/k/kko9x2bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wznngcc3g"/><path class="tk3p5zjbs"/><path class="kko9x2bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crew-transfer-vessel-48" /></template>
