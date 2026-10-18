<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq77azrkm.css';
import '../../css/o/oykk7m8it.css';
import '../../css/q/qkfd58nsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hq77azrkm"/><path class="oykk7m8it"/><path class="qkfd58nsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hi-vis-vest-20" /></template>
