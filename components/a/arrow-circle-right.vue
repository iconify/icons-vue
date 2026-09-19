<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afci7hbne.css';
import '../../css/g/g1m3d2bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="afci7hbne"/><path class="g1m3d2bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:arrow-circle-right" /></template>
