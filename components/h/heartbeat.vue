<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esle7_bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="esle7_bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:heartbeat" /></template>
