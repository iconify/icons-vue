<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwxhpy1gt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwxhpy1gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lock" /></template>
