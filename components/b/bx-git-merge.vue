<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlb_9o8_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlb_9o8_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-git-merge" /></template>
