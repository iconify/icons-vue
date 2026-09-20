<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbr5azbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbr5azbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:face-smile2-filled" /></template>
