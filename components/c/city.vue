<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8tgevb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m8tgevb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:city" /></template>
