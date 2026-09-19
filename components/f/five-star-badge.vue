<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rinuwhlnp.css';
import '../../css/i/ipmfw8jim.css';
import '../../css/n/npkoh8bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="rinuwhlnp"><path class="ipmfw8jim"/><path class="npkoh8bln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:five-star-badge" /></template>
