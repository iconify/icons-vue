<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y33rdabgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y33rdabgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:container-fill" /></template>
