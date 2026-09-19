<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbht7_vyu.css';
import '../../css/h/hxw8-dzsl.css';
import '../../css/f/f_pda4xwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tbht7_vyu"/><path class="hxw8-dzsl"/><path class="f_pda4xwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-cut" /></template>
