<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1mjunbsu.css';
import '../../css/c/c4ksj3b6a.css';
import '../../css/k/k4nj-ld-c.css';
import '../../css/q/qlms35rim.css';
import '../../css/w/w49j0rbvv.css';
import '../../css/t/tb2tmcbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGGci1Obvw"><g class="n1mjunbsu"><path fill-opacity="0" class="c4ksj3b6a"><animate fill="freeze" attributeName="stroke-dashoffset" dur="0.6s" values="60;0"/><animate fill="freeze" attributeName="fill-opacity" begin="0.6s" dur="0.15s" to=".3"/></path><path d="M11 11l1 1l1 1l-1 -1Z" transform="rotate(-180 12 12)"><animate fill="freeze" attributeName="d" begin="0.85s" dur="0.3s" to="M10.2 10.2l6.8 -3.2l-3.2 6.8l-6.8 3.2Z"/><animateTransform fill="freeze" attributeName="transform" begin="0.85s" dur="0.5s" type="rotate" values="-180 12 12;0 12 12"/></path></g><circle class="k4nj-ld-c"><animate fill="freeze" attributeName="r" begin="0.85s" dur="0.3s" to="1"/></circle><path stroke-dashoffset="28" transform="rotate(45 12 12)" class="qlms35rim"><animate fill="freeze" attributeName="stroke-dashoffset" begin="1.35s" dur="0.4s" to="0"/></path></mask></defs><path mask="url(#SVGGci1Obvw)" class="w49j0rbvv"/><path stroke-dashoffset="28" transform="rotate(45 12 12)" class="tb2tmcbqs"><animate fill="freeze" attributeName="stroke-dashoffset" begin="1.35s" dur="0.4s" to="0"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:compass-twotone-off" /></template>
