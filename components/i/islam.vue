<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-r3bw6mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-r3bw6mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:islam" /></template>
