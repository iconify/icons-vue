<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk93trgoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vk93trgoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:buddicons-buddypress-logo" /></template>
