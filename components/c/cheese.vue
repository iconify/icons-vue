<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxa0j-bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mxa0j-bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cheese" /></template>
