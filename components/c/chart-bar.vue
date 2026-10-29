<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onlbud-6m.css';
import '../../css/z/z3dt8qrmb.css';
import '../../css/l/ljw94hbdi.css';
import '../../css/m/mn_fpfo9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onlbud-6m wm-k"/><path class="wm-k z3dt8qrmb"/><path class="ljw94hbdi wm-k"/><path class="mn_fpfo9f wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:chart-bar" /></template>
