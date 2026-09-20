<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l503qdb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l503qdb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flag-outline" /></template>
