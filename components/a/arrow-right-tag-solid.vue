<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx8s_cbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vx8s_cbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-right-tag-solid" /></template>
