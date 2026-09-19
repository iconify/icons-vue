<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rinuwhlnp.css';
import '../../css/b/bshyy_b6k.css';
import '../../css/g/g50eo_bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="rinuwhlnp"><circle class="bshyy_b6k"/><path class="g50eo_bim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:girl-one" /></template>
