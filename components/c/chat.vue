<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn7_n8brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kn7_n8brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:chat" /></template>
