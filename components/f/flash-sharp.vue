<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-lo8vbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s-lo8vbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:flash-sharp" /></template>
