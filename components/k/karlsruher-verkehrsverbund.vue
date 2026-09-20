<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkrd80bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkrd80bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:karlsruher-verkehrsverbund" /></template>
