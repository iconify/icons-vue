<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo63ynbwm.css';
import '../../css/l/lancvpb5m.css';
import '../../css/x/xk9l3dbcq.css';
import '../../css/d/d_qns109m.css';
import '../../css/p/p26ovwc5b.css';
import '../../css/w/w-9uz_bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="fo63ynbwm"/><path class="lancvpb5m"/><path class="xk9l3dbcq"/><path class="d_qns109m"/><path class="p26ovwc5b"/><path class="w-9uz_bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:julia" /></template>
