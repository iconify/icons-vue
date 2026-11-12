<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbtomab4q.css';
import '../../css/t/tytji7n_q.css';
import '../../css/e/egb1_lbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="lbtomab4q"/><path class="tytji7n_q"/><path class="egb1_lbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbpad" /></template>
