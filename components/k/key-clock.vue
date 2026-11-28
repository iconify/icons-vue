<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywdy1lytn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywdy1lytn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:key-clock" /></template>
