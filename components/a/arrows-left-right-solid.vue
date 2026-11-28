<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1x_9gqov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1x_9gqov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrows-left-right-solid" /></template>
