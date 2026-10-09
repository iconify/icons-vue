<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prrieubjn.css';
import '../../css/o/o1dca9b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="prrieubjn"/><path class="o1dca9b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lock-20" /></template>
