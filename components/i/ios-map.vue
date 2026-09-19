<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p22exlb2q.css';
import '../../css/s/stmks3bbg.css';
import '../../css/t/tpw__yb9r.css';
import '../../css/k/k3wk1kf1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p22exlb2q"/><path class="stmks3bbg"/><path class="tpw__yb9r"/><path class="k3wk1kf1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-map" /></template>
