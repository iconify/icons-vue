<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gua1uqcfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gua1uqcfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-arrow-right-outline" /></template>
