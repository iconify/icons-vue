<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui-320b_k.css';
import '../../css/m/mgacobbqu.css';
import '../../css/u/u9e3mk9nq.css';
import '../../css/j/j6qaewbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui-320b_k"/><path class="mgacobbqu"/><path class="u9e3mk9nq"/><path class="j6qaewbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:e-commerce-basket-monitor" /></template>
