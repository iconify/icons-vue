<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzs6f0bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zzs6f0bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:compress" /></template>
