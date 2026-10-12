<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiecv_t_z.css';
import '../../css/w/wryrt8b-k.css';
import '../../css/f/f5yzw-ygz.css';
import '../../css/u/ulazcvbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aiecv_t_z"/><path class="wryrt8b-k"/><path class="f5yzw-ygz"/><path class="ulazcvbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ambulance-48-bold" /></template>
