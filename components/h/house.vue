<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txy313exu.css';
import '../../css/t/tvxuj9beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="txy313exu"/><path class="tvxuj9beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:house" /></template>
