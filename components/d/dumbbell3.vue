<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggg5zfbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ggg5zfbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:dumbbell3" /></template>
