<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lffg11dkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lffg11dkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:ceiling-lamp" /></template>
