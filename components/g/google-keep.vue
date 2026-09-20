<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ind_uwmve.css';
import '../../css/y/y5z6dwezu.css';
import '../../css/g/g2lri_b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ind_uwmve"/><path class="y5z6dwezu"/><path class="g2lri_b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-keep" /></template>
