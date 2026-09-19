<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/h_l78yaxm.css';
import '../../css/p/pvy_1nbjw.css';
import '../../css/u/ugb540alo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><ellipse class="h_l78yaxm"/><path class="pvy_1nbjw"/><path class="ugb540alo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:database-zap" /></template>
