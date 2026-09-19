<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwup2nbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jwup2nbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:alert-sharp" /></template>
