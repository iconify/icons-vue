<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8t5zg48u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n8t5zg48u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:controls-repeat" /></template>
