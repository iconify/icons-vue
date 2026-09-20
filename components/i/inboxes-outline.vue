<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyefgj2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuyefgj2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:inboxes-outline" /></template>
