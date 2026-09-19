<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkz5hvbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="rkz5hvbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:dice-four" /></template>
