<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrj4jebuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrj4jebuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-alt-shield" /></template>
