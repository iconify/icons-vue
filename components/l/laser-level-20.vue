<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg0u5tbyf.css';
import '../../css/q/qnjki0hlv.css';
import '../../css/j/jf1_jq5jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zg0u5tbyf"/><path class="qnjki0hlv"/><path class="jf1_jq5jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:laser-level-20" /></template>
