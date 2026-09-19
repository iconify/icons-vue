<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi-ez7b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi-ez7b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:glasses" /></template>
