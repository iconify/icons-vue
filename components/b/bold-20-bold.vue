<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eysowxhrp.css';
import '../../css/s/seio_1p-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eysowxhrp"/><path class="seio_1p-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bold-20-bold" /></template>
