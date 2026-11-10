<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihyzhxboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ihyzhxboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:calendar-exclamation-solid" /></template>
