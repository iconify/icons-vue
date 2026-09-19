<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob03_5z6s.css';
import '../../css/y/ya_ah-bgp.css';
import '../../css/q/q6q3hcc8y.css';
import '../../css/l/leddtrblw.css';
import '../../css/r/rz66g3bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="ob03_5z6s"/><circle class="ya_ah-bgp"/><path class="q6q3hcc8y"/><path class="leddtrblw"/><circle class="rz66g3bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:cut-outline" /></template>
