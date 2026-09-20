<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le6bjebxm.css';
import '../../css/c/ct-rsubrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le6bjebxm"/><path class="ct-rsubrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-broken-bold" /></template>
