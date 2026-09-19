<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj9il9vdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qj9il9vdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:dolly" /></template>
