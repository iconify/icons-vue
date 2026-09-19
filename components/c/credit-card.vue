<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbqm40wsr.css';
import '../../css/x/xgj3z1bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bbqm40wsr"/><path class="xgj3z1bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:credit-card" /></template>
