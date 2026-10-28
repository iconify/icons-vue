<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iveed3bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iveed3bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:emirati-dirham" /></template>
