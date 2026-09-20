<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtw1qacud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wtw1qacud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alaska-airlines-light" /></template>
