<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxvidob-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="lxvidob-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand-holding-hand" /></template>
