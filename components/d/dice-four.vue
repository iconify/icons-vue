<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntc9-ffnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ntc9-ffnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:dice-four" /></template>
