<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4r73fbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4r73fbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:film" /></template>
