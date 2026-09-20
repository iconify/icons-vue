<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv09q5bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv09q5bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:airserbia" /></template>
