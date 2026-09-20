<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjcralbgb.css';
import '../../css/c/c69tzz_ao.css';
import '../../css/x/x01tv3b7d.css';
import '../../css/q/qsb2wdkcm.css';
import '../../css/o/or-s3ab2l.css';
import '../../css/o/oidwmib6t.css';
import '../../css/q/q8rlsqbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wjcralbgb"/><path clip-rule="evenodd" class="c69tzz_ao"/><path clip-rule="evenodd" class="x01tv3b7d"/><path clip-rule="evenodd" class="qsb2wdkcm"/><path clip-rule="evenodd" class="or-s3ab2l"/><path class="oidwmib6t"/><path class="q8rlsqbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:grav" /></template>
