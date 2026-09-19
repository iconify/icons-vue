<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drytl15lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="drytl15lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:albums-sharp" /></template>
