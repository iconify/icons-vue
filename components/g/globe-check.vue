<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaxx-ccaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qaxx-ccaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:globe-check" /></template>
