<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqdbu0ewy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqdbu0ewy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bell-off" /></template>
