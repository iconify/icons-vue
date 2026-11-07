<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk9skhkui.css';
import '../../css/q/qqlpehxim.css';
import '../../css/f/fe61ukfco.css';
import '../../css/m/mdfdrlbhr.css';
import '../../css/b/bsmairrif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk9skhkui"/><path class="qqlpehxim"/><path class="fe61ukfco"/><path class="mdfdrlbhr"/><path class="bsmairrif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:binoculars-outline" /></template>
