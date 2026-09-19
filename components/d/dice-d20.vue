<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpjvekbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qpjvekbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:dice-d20" /></template>
