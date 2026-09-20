<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxbaafedr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxbaafedr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-down-circle-fill-2" /></template>
