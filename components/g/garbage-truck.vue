<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bf9hqaclw.css';
import '../../css/e/ec_xsy4gs.css';
import '../../css/a/a0kd3v4hr.css';
import '../../css/x/xdd7caceh.css';
import '../../css/d/dc5f50e_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="bf9hqaclw"/><circle class="ec_xsy4gs"/><path class="a0kd3v4hr"/><path class="xdd7caceh"/><path class="dc5f50e_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:garbage-truck" /></template>
