<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o68lzb7-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o68lzb7-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:command-solid" /></template>
