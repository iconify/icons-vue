<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6-xxm_2j.css';
import '../../css/q/qk15utbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6-xxm_2j"/><path class="qk15utbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cricket-ball" /></template>
