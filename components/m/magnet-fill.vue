<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we18llb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="we18llb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:magnet-fill" /></template>
