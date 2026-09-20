<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brx7nk65y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brx7nk65y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:food-weiner" /></template>
