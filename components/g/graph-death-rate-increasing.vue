<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qozqv2b1b.css';
import '../../css/g/gyiyzcbpy.css';
import '../../css/d/dcofopror.css';
import '../../css/c/ck7wznqzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qozqv2b1b"/><path class="gyiyzcbpy"/><path class="dcofopror"/><path class="ck7wznqzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:graph-death-rate-increasing" /></template>
