<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luy5b2qht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="luy5b2qht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gate-and" /></template>
