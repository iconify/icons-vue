<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9d_yabpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9d_yabpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:battery-low-sharp" /></template>
