<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgpzimtyu.css';
import '../../css/q/qulyerb_t.css';
import '../../css/v/vddp-gbtw.css';
import '../../css/d/dpm5hf-1w.css';
import '../../css/u/umy3w9bnm.css';
import '../../css/a/ahbf3vjsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hgpzimtyu"/><circle class="qulyerb_t"/><circle class="vddp-gbtw"/><circle class="dpm5hf-1w"/><circle class="umy3w9bnm"/><circle class="ahbf3vjsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-scatter" /></template>
