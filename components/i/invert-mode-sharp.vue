<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek96bfbmm.css';
import '../../css/l/lyo-h1s_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ek96bfbmm"/><path class="lyo-h1s_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:invert-mode-sharp" /></template>
