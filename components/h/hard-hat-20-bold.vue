<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psoacabks.css';
import '../../css/w/wtf21ym8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="psoacabks"/><path class="wtf21ym8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hard-hat-20-bold" /></template>
