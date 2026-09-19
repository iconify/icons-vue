<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqcs72gla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yqcs72gla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:battery-low-solid" /></template>
