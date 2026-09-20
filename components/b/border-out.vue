<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk0_w_boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk0_w_boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:border-out" /></template>
