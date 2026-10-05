<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/i/i6psyz68x.css';
import '../../css/o/o6ain5brh.css';
import '../../css/p/p_u131ihg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="i6psyz68x"/><path class="o6ain5brh"/><path class="p_u131ihg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:download" /></template>
