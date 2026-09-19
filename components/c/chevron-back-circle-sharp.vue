<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp-is2bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fp-is2bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chevron-back-circle-sharp" /></template>
