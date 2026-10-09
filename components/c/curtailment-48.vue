<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-py7pbjn.css';
import '../../css/d/d59gayyww.css';
import '../../css/m/m0ym9zbob.css';
import '../../css/c/c_xh25dlx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u-py7pbjn"/><path class="d59gayyww"/><path class="m0ym9zbob"/><path class="c_xh25dlx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:curtailment-48" /></template>
