<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/argozxbrb.css';
import '../../css/g/gtd6d5jyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="argozxbrb"/><path class="gtd6d5jyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevrons-down-up-outline" /></template>
