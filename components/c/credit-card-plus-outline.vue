<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvax7ob5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvax7ob5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:credit-card-plus-outline" /></template>
