<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd1sg2zja.css';
import '../../css/z/z-px0kjof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd1sg2zja"/><path class="z-px0kjof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-power-off" /></template>
