<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtcji1bya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtcji1bya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:list-bullet" /></template>
