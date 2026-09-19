<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2oxu-1qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2oxu-1qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chat-feedback-01" /></template>
