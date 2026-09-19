<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo7m9ebwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo7m9ebwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:intel-cpu" /></template>
