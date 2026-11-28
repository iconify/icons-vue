<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm6oswlyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm6oswlyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:island" /></template>
