<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig7m_j8ip.css';
import '../../css/f/f8paaybnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig7m_j8ip"/><path class="f8paaybnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:book-open-check-filled" /></template>
