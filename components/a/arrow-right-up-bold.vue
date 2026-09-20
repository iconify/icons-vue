<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn9p7b49h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn9p7b49h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-up-bold" /></template>
