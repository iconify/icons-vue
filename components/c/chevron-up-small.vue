<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i12dm4t4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i12dm4t4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chevron-up-small" /></template>
