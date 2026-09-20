<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuf2nkvgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuf2nkvgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-triple-left" /></template>
