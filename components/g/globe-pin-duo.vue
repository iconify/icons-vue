<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atdwg2krv.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l11ovjb-s.css';
import '../../css/q/qw6pybb1f.css';
import '../../css/t/t-bwbsbwy.css';
import '../../css/j/j0tm0dnhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atdwg2krv secondary"/><g class="dt0cm9dhy primary"><path class="l11ovjb-s"/><path class="qw6pybb1f"/><path class="t-bwbsbwy"/><path class="j0tm0dnhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:globe-pin-duo" /></template>
