<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0t4ebqbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0t4ebqbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-corner-up-right" /></template>
