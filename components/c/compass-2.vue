<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckf3fdcmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ckf3fdcmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:compass-2" /></template>
