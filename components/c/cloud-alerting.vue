<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opaq2dbry.css';
import '../../css/r/rqqek-bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="opaq2dbry"/><path class="rqqek-bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cloud-alerting" /></template>
