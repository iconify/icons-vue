<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii3fyacso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii3fyacso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:briefcase-4-line" /></template>
