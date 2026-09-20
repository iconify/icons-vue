<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vup6mgjcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vup6mgjcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:cairometro" /></template>
