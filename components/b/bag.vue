<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr2sukbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kr2sukbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:bag" /></template>
