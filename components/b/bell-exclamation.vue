<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzfljrblz.css';
import '../../css/s/saso1vbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xzfljrblz"/><path class="saso1vbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:bell-exclamation" /></template>
