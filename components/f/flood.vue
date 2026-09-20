<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj54ll90s.css';
import '../../css/n/nxzuqf7tr.css';
import '../../css/r/rds-sv7pp.css';
import '../../css/u/uyrysvt3k.css';
import '../../css/l/lhiif9hem.css';
import '../../css/q/q3g9qac4w.css';
import '../../css/g/gsb2qybke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="sj54ll90s"/><path class="nxzuqf7tr"/><path class="rds-sv7pp"/><path class="uyrysvt3k"/><path class="lhiif9hem"/><path class="q3g9qac4w"/><path class="gsb2qybke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flood" /></template>
