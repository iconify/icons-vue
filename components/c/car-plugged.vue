<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/wa5lu2h4f.css';
import '../../css/f/fn_w7lggo.css';
import '../../css/l/lh7j9tb9s.css';
import '../../css/j/jx0oupbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wa5lu2h4f"/><circle class="fn_w7lggo"/><circle class="lh7j9tb9s"/><path class="jx0oupbir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:car-plugged" /></template>
