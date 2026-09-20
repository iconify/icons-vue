<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzob4b76j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzob4b76j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:led-strip-variant" /></template>
