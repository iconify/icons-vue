<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gahn8ob2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gahn8ob2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chat-off" /></template>
