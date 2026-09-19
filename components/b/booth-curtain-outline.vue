<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqsabac0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqsabac0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:booth-curtain-outline" /></template>
