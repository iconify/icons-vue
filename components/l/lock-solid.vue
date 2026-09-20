<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4mplaboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4mplaboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:lock-solid" /></template>
