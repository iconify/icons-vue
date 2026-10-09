<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bejh_pbmo.css';
import '../../css/s/s5qakmbbz.css';
import '../../css/u/ux699tbwn.css';
import '../../css/v/v_7pz1b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bejh_pbmo"/><path class="s5qakmbbz"/><path class="ux699tbwn"/><path class="v_7pz1b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:geothermal-well-20" /></template>
