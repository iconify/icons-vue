<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6b8s_bci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="c6b8s_bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:fisted-hand-sign" /></template>
