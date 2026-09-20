<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djude9bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djude9bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flag-checkered-variant" /></template>
