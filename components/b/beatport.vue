<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwmq47vio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwmq47vio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:beatport" /></template>
