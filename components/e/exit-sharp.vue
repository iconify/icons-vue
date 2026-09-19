<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/heq7cyb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="heq7cyb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:exit-sharp" /></template>
