<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox5zndcug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ox5zndcug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:hairdresser-14" /></template>
