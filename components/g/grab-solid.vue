<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj2p-4bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj2p-4bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:grab-solid" /></template>
