<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld8w7hb7k.css';
import '../../css/h/hp_ny3_4l.css';
import '../../css/c/cqnbl8q7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="ld8w7hb7k"/><rect class="hp_ny3_4l"/><path class="cqnbl8q7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:battery-full-outline" /></template>
