<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9j6-o0-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9j6-o0-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:brackets-angled" /></template>
