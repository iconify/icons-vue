<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/b9nw66bsr.css';
import '../../css/l/lqlm572ur.css';
import '../../css/r/rwz-1vx6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b9nw66bsr"/><path class="lqlm572ur"/><path class="rwz-1vx6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:covid19-virus-heal-1" /></template>
