<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8g_y9igt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q8g_y9igt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-down-outline" /></template>
