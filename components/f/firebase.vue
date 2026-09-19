<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shnmxq6pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shnmxq6pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:firebase" /></template>
