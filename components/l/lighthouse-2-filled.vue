<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf4f4fryy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf4f4fryy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:lighthouse-2-filled" /></template>
