<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v460hd2nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v460hd2nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:globe-cog-solid" /></template>
