<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-v8w7bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-v8w7bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:head-heart" /></template>
