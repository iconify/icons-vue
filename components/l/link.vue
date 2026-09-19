<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arx4ecvuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arx4ecvuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:link" /></template>
