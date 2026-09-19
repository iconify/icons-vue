<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhxm0b_ck.css';
import '../../css/h/hf_7z-k3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="hhxm0b_ck"/><path class="hf_7z-k3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ban" /></template>
