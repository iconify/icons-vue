<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzl577bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzl577bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dumbbell-large-bold" /></template>
