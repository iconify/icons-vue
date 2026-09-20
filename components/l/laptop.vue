<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0o93bc9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0o93bc9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:laptop" /></template>
