<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0sqvp_wh.css';
import '../../css/e/eny6z_bgj.css';
import '../../css/g/gzwu-mp2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0sqvp_wh"/><path class="eny6z_bgj"/><path class="gzwu-mp2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:envelope-sealed-bold" /></template>
