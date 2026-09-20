<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5nyh0bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5nyh0bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-dollar" /></template>
