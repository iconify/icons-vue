<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/seti68b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="seti68b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:battery-charging" /></template>
