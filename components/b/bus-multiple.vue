<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2bn64t8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2bn64t8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bus-multiple" /></template>
