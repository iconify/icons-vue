<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pawdocb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pawdocb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bulb-cfl" /></template>
