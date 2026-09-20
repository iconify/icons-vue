<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3x0uu0wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3x0uu0wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dollar-off" /></template>
