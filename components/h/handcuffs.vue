<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygj57klac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ygj57klac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:handcuffs" /></template>
