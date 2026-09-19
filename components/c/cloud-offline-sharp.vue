<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi1xcw0cd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xi1xcw0cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:cloud-offline-sharp" /></template>
