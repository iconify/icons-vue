<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs4i_ac-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cs4i_ac-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:data-transfer-down" /></template>
