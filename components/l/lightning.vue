<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8ehmpvfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="y8ehmpvfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:lightning" /></template>
