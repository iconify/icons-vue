<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofzz_rb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofzz_rb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-quote-outline" /></template>
