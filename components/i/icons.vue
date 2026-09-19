<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om4a-sm7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="om4a-sm7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:icons" /></template>
