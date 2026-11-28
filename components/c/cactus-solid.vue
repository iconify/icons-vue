<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9blg-1qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9blg-1qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cactus-solid" /></template>
