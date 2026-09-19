<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_y4tmboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z_y4tmboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:flash-off-sharp" /></template>
