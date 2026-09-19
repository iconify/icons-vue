<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-pyd0_-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-pyd0_-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:info" /></template>
