<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drphl9x-c.css';
import '../../css/q/q6evf3_3i.css';
import '../../css/a/a8z3xdbuh.css';
import '../../css/n/n3fso8b_j.css';
import '../../css/a/ay8131wny.css';
import '../../css/a/aqkjjjv3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="drphl9x-c"/><path class="q6evf3_3i"/><path class="a8z3xdbuh"/><path class="n3fso8b_j"/><circle class="ay8131wny"/><path class="aqkjjjv3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:blue-book" /></template>
