<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_0ryua6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_0ryua6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-arrow-up-right-fill-round" /></template>
