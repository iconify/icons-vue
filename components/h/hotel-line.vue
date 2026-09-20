<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puwkpfzjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="puwkpfzjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hotel-line" /></template>
