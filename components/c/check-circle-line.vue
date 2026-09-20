<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps9665bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps9665bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:check-circle-line" /></template>
