<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3l1hd7pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3l1hd7pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bowl-fill" /></template>
