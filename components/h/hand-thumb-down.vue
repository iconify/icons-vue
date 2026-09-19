<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9anfdc5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9anfdc5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:hand-thumb-down" /></template>
