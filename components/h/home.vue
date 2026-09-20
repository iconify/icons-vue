<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka1p2wyfl.css';
import '../../css/n/ng_udhb8v.css';
import '../../css/g/g4-q86_8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka1p2wyfl"/><path class="ng_udhb8v"/><path class="g4-q86_8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:home" /></template>
