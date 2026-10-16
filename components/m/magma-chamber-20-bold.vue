<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5lwlib7c.css';
import '../../css/l/l6xpa5bsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l5lwlib7c"/><path class="l6xpa5bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:magma-chamber-20-bold" /></template>
