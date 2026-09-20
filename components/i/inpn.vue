<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imhf5wbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="imhf5wbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:inpn" /></template>
