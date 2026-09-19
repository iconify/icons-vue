<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxoyierhi.css';
import '../../css/d/dwqux_e7p.css';
import '../../css/w/wozsguqxs.css';
import '../../css/s/sw1ncqnov.css';
import '../../css/q/qgz_s6bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jxoyierhi"/><path class="dwqux_e7p"/><path class="wozsguqxs"/><path class="sw1ncqnov"/><path class="qgz_s6bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:angularjs" /></template>
