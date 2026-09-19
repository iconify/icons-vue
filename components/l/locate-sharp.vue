<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3c6jabxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l3c6jabxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:locate-sharp" /></template>
