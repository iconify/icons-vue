<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtdiujbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="qtdiujbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:boat-tour" /></template>
