<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdh-geker.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdh-geker"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:av-receiver-off" /></template>
