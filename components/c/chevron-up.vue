<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id1aojbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id1aojbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:chevron-up" /></template>
