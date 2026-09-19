<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abmtkcbyd.css';
import '../../css/c/ctjrvzbee.css';
import '../../css/q/q_c-66bgc.css';
import '../../css/z/zcu-748sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="abmtkcbyd"/><rect class="ctjrvzbee"/><rect class="q_c-66bgc"/><rect class="zcu-748sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:grid-outline" /></template>
