<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/eedy2_2_u.css';
import '../../css/j/jyg2dbbxi.css';
import '../../css/d/d69r_jv7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="eedy2_2_u"/><path class="jyg2dbbxi"/><path class="d69r_jv7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:club" /></template>
