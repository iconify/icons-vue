<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnnithbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnnithbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cannabis-off" /></template>
