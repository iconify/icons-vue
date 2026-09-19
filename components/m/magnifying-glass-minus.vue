<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j53nm-bpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j53nm-bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:magnifying-glass-minus" /></template>
