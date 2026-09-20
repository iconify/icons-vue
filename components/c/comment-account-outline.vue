<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkqtxxnbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkqtxxnbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-account-outline" /></template>
