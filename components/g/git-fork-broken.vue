<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f8m9b9b9z.css';
import '../../css/f/fn1p5fm9f.css';
import '../../css/x/x1se1px2n.css';
import '../../css/i/i3ie3ccuz.css';
import '../../css/r/r50xlibql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f8m9b9b9z"/><path class="fn1p5fm9f"/><path class="x1se1px2n"/><path class="i3ie3ccuz"/><path class="r50xlibql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-fork-broken" /></template>
