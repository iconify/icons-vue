<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/powor1xqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="powor1xqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:briefcase-fill-round" /></template>
