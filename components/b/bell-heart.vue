<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5hyo8b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5hyo8b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-heart" /></template>
