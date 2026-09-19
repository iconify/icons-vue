<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6u7cmg7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6u7cmg7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:claude" /></template>
