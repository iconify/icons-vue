<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9-9zsb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9-9zsb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-up-linear" /></template>
