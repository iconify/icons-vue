<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ium9azweu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ium9azweu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:chart-diagram" /></template>
