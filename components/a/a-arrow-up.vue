<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyq6sxb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyq6sxb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:a-arrow-up" /></template>
