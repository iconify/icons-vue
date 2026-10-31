<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6mogacyz.css';
import '../../css/r/raky5r2xx.css';
import '../../css/n/n_rsox0pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="g6mogacyz"/><path class="raky5r2xx"/><path class="n_rsox0pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:bolivia" /></template>
