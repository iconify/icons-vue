<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5tsb6jyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5tsb6jyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-down-linear" /></template>
