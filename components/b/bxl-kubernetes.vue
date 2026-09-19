<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4zh9ut5i.css';
import '../../css/j/jumj_bc-f.css';
import '../../css/a/aww_3tzev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4zh9ut5i"/><path class="jumj_bc-f"/><path class="aww_3tzev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-kubernetes" /></template>
