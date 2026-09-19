<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_vkl9uws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="c_vkl9uws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:eight-of-circles-mahjong-filled" /></template>
