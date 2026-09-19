<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/y/y6f0jibvm.css';
import '../../css/y/yicpnf2jv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="y6f0jibvm"/><rect transform="rotate(45 24 16.929)" class="yicpnf2jv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:financing" /></template>
