<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgwo3tb-z.css';
import '../../css/w/wz53a60hh.css';
import '../../css/v/v1p4ihz6t.css';
import '../../css/i/ifcw9tbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cgwo3tb-z"/><path class="wz53a60hh"/><path class="v1p4ihz6t"/><path class="ifcw9tbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:concentrated-solar-48" /></template>
