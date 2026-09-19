<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4-w4rbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="s4-w4rbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:images" /></template>
