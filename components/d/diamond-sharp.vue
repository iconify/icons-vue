<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhfnrfbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mhfnrfbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:diamond-sharp" /></template>
