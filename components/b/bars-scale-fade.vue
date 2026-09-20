<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv67n12_i.css';
import '../../css/i/idk-qbbqo.css';
import '../../css/z/zrl8ulbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect height="14" y="4" class="zv67n12_i"><animate id="SVGBoZ3Ab9F" fill="freeze" attributeName="y" begin="0;SVG0XJl4OCs.end-0.25s" dur="0.75s" values="1;5"/><animate fill="freeze" attributeName="height" begin="0;SVG0XJl4OCs.end-0.25s" dur="0.75s" values="22;14"/><animate fill="freeze" attributeName="opacity" begin="0;SVG0XJl4OCs.end-0.25s" dur="0.75s" values="1;.2"/></rect><rect height="14" y="4" opacity=".4" class="idk-qbbqo"><animate fill="freeze" attributeName="y" begin="SVGBoZ3Ab9F.begin+0.15s" dur="0.75s" values="1;5"/><animate fill="freeze" attributeName="height" begin="SVGBoZ3Ab9F.begin+0.15s" dur="0.75s" values="22;14"/><animate fill="freeze" attributeName="opacity" begin="SVGBoZ3Ab9F.begin+0.15s" dur="0.75s" values="1;.2"/></rect><rect height="14" y="4" opacity=".3" class="zrl8ulbxn"><animate id="SVG0XJl4OCs" fill="freeze" attributeName="y" begin="SVGBoZ3Ab9F.begin+0.3s" dur="0.75s" values="1;5"/><animate fill="freeze" attributeName="height" begin="SVGBoZ3Ab9F.begin+0.3s" dur="0.75s" values="22;14"/><animate fill="freeze" attributeName="opacity" begin="SVGBoZ3Ab9F.begin+0.3s" dur="0.75s" values="1;.2"/></rect>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="svg-spinners:bars-scale-fade" /></template>
