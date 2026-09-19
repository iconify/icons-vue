<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/n/ncir--e1f.css';
import '../../css/q/q1zl0lc0k.css';
import '../../css/s/s7i40lndy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ncir--e1f"/><path class="q1zl0lc0k"/><path class="s7i40lndy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-art" /></template>
