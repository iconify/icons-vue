<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o16-f-blb.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/z_5v93bby.css';
import '../../css/x/x3nck_bwk.css';
import '../../css/x/xdkyl9b-v.css';
import '../../css/z/z8ixs7b-k.css';
import '../../css/o/or5248bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o16-f-blb secondary"/><g class="dt0cm9dhy primary"><path class="z_5v93bby"/><path class="x3nck_bwk"/><path class="xdkyl9b-v"/><path class="z8ixs7b-k"/><path class="or5248bfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:certificate-duo" /></template>
