<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/a/at0wocbmy.css';
import '../../css/r/rk2p0fx6y.css';
import '../../css/b/b6ri4w3zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="at0wocbmy"/><path class="rk2p0fx6y"/><path class="b6ri4w3zb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:diagram-split-horizontal" /></template>
