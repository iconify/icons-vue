<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caag8rbrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caag8rbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-arrow-out-up-right-fill" /></template>
