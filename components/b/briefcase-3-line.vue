<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo4dh6bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo4dh6bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:briefcase-3-line" /></template>
