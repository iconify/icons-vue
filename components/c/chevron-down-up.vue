<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q38v2vbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q38v2vbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chevron-down-up" /></template>
