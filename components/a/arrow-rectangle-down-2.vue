<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/h6xo0_btj.css';
import '../../css/b/b3c550_rl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h6xo0_btj"/><path clip-rule="evenodd" class="b3c550_rl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:arrow-rectangle-down-2" /></template>
