<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6maa3bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o6maa3bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:clock-rotate-left" /></template>
