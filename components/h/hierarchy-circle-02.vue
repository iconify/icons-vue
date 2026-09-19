<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gglsf5jgx.css';
import '../../css/k/kxe36xeye.css';
import '../../css/k/kc3talsdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gglsf5jgx"/><path class="kxe36xeye"/><path class="kc3talsdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hierarchy-circle-02" /></template>
