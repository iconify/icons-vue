<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg2497qtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg2497qtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:gumroad" /></template>
