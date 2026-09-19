<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hth-q-b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hth-q-b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:ban" /></template>
