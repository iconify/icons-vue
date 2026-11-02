<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt2w29brp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt2w29brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eye-close-fill" /></template>
