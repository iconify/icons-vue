<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6kyv-7dy.css';
import '../../css/k/k033u8bmd.css';
import '../../css/a/apa-nuboc.css';
import '../../css/t/t2ol4rbbp.css';
import '../../css/g/gjzzc-b5h.css';
import '../../css/e/e_4h_dc1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t6kyv-7dy"/><path class="k033u8bmd"/><path class="apa-nuboc"/><path class="t2ol4rbbp"/><path class="gjzzc-b5h"/><path class="e_4h_dc1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:krusader" /></template>
