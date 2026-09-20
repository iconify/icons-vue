<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxr9j-bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxr9j-bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:magnet-on" /></template>
