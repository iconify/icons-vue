<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbzmt7bhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kbzmt7bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:klipper-dark" /></template>
