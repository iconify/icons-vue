<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5g6wl4un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u5g6wl4un"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-up-outline" /></template>
