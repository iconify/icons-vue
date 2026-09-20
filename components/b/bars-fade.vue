<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql9ledqyz.css';
import '../../css/f/fej-fccjd.css';
import '../../css/d/d1afhdbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="ql9ledqyz"><animate id="SVG9ovaHbIP" fill="freeze" attributeName="opacity" begin="0;SVGa89dAd4w.end-0.25s" dur="0.75s" values="1;.2"/></rect><rect opacity=".4" class="fej-fccjd"><animate fill="freeze" attributeName="opacity" begin="SVG9ovaHbIP.begin+0.15s" dur="0.75s" values="1;.2"/></rect><rect opacity=".3" class="d1afhdbwl"><animate id="SVGa89dAd4w" fill="freeze" attributeName="opacity" begin="SVG9ovaHbIP.begin+0.3s" dur="0.75s" values="1;.2"/></rect>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="svg-spinners:bars-fade" /></template>
