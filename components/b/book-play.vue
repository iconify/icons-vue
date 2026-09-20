<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avyfizbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avyfizbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-play" /></template>
