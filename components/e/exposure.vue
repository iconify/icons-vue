<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krm_rrbhp.css';
import '../../css/q/q1h9w_bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="krm_rrbhp"/><path class="q1h9w_bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:exposure" /></template>
