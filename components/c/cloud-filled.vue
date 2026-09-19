<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dajrud2vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dajrud2vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cloud-filled" /></template>
