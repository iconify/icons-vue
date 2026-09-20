<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx2ml4aqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx2ml4aqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate-color:arrow-button-right-1" /></template>
