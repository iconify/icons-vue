<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccmeg2w-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ccmeg2w-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:arrow-forward-circle-sharp" /></template>
