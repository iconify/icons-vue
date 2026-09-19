<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty3029wgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ty3029wgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:female-sharp" /></template>
