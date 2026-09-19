<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntr_u1-hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ntr_u1-hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-tux" /></template>
