<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnxjfyb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnxjfyb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bold" /></template>
