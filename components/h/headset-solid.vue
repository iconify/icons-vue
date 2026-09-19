<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipba9j3av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipba9j3av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:headset-solid" /></template>
