<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/z/zn1_-h4qq.css';
import '../../css/t/ttwa5ubjw.css';
import '../../css/p/plicdh0bi.css';
import '../../css/i/i44_mrbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zn1_-h4qq"/><path class="ttwa5ubjw"/><path class="plicdh0bi"/><path class="i44_mrbsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:empty-wallet-tick" /></template>
