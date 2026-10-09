<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv7_8fbub.css';
import '../../css/s/sgaegpv7c.css';
import '../../css/f/fv65liyxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hv7_8fbub"/><path class="sgaegpv7c"/><path class="fv65liyxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:git-pull-request-20" /></template>
