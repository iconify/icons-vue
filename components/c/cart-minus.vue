<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtwzzdbkp.css';
import '../../css/r/rri86bcuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtwzzdbkp"/><path class="rri86bcuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:cart-minus" /></template>
