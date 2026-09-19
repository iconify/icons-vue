<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx2-8-56a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="fx2-8-56a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:check-double" /></template>
