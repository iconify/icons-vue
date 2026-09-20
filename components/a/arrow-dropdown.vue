<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-k_55dvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-k_55dvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-dropdown" /></template>
