<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1qrgebiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1qrgebiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crown-minimalistic-linear" /></template>
