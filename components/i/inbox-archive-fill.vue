<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa7-4xb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa7-4xb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:inbox-archive-fill" /></template>
