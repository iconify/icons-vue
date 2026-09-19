<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2tprwbpc.css';
import '../../css/v/vwxhrfbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="x2tprwbpc"/><path class="vwxhrfbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:flower-sharp" /></template>
