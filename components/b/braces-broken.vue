<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/u/u29u3ubqq.css';
import '../../css/b/bws08ccji.css';
import '../../css/b/by1hc2n7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u29u3ubqq"/><path class="bws08ccji"/><path class="by1hc2n7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:braces-broken" /></template>
