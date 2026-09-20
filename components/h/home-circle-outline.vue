<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgbz6kbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgbz6kbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-circle-outline" /></template>
