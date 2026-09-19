<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq5_7wbcb.css';
import '../../css/i/iinzih3vq.css';
import '../../css/q/qj6k40n7i.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="bq5_7wbcb clr-i-outline--badged clr-i-outline-path-1--badged"/><path class="clr-i-outline--badged clr-i-outline-path-2--badged iinzih3vq"/><path class="clr-i-outline--badged clr-i-outline-path-3--badged qj6k40n7i"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-4--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:box-plot-outline-badged" /></template>
