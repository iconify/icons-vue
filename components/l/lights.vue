<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtp6h5bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtp6h5bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lights" /></template>
