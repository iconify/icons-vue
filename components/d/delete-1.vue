<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2k4tnisn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="g2k4tnisn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:delete-1" /></template>
