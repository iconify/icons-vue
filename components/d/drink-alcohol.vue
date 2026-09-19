<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw83f75la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fw83f75la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:drink-alcohol" /></template>
