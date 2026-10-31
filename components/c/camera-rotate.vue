<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7enucrlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7enucrlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:camera-rotate" /></template>
