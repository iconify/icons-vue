<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_gzed_lp.css';
import '../../css/s/sed9x-mdd.css';
import '../../css/c/cjftz1f6d.css';
import '../../css/a/aiqt_ub4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m_gzed_lp"/><path class="sed9x-mdd"/><path class="cjftz1f6d"/><path class="aiqt_ub4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:anchor-48-bold" /></template>
