<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fujqedbkp.css';
import '../../css/e/e15e1_l3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fujqedbkp"/><path class="e15e1_l3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:codeberg-light" /></template>
