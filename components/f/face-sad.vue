<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fndgsfbhl.css';
import '../../css/o/ooafjrbnh.css';
import '../../css/v/vd27ehbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fndgsfbhl"/><path class="ooafjrbnh"/><path class="vd27ehbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:face-sad" /></template>
