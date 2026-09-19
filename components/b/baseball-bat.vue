<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly6jl_bkj.css';
import '../../css/z/zrcrh4bnb.css';
import '../../css/j/j0-a04gjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ly6jl_bkj"><circle class="zrcrh4bnb"/><path class="j0-a04gjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:baseball-bat" /></template>
