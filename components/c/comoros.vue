<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ube0ylbed.css';
import '../../css/d/d73ovybpc.css';
import '../../css/u/upkzhhbkg.css';
import '../../css/f/f-ozn4blu.css';
import '../../css/m/m-3w7fb6z.css';
import '../../css/h/h-u7p0bzv.css';
import '../../css/t/tpp_zt08c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="ube0ylbed"/><path class="d73ovybpc"/><path class="upkzhhbkg"/><path class="f-ozn4blu"/><path class="m-3w7fb6z"/><path class="h-u7p0bzv"/><path class="tpp_zt08c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:comoros" /></template>
