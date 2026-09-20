<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeghuabay.css';
import '../../css/g/gb3vxeboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xeghuabay"/><path class="gb3vxeboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jetkvm" /></template>
