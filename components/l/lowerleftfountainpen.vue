<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r35rppbpm.css';
import '../../css/y/yjyw_obwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r35rppbpm"/><path class="yjyw_obwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:lowerleftfountainpen" /></template>
