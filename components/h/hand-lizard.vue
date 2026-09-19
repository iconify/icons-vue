<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt869bbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vt869bbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:hand-lizard" /></template>
