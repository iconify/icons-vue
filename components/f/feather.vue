<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im2qk3bnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im2qk3bnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:feather" /></template>
