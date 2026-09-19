<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4_g4nd3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n4_g4nd3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:cloud-outline" /></template>
