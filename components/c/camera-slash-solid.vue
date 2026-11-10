<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd6l3mgky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cd6l3mgky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:camera-slash-solid" /></template>
