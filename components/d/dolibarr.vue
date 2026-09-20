<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xenwn65bw.css';
import '../../css/p/pb3h_qhil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xenwn65bw"/><ellipse class="pb3h_qhil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dolibarr" /></template>
