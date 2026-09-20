<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut64ajb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ut64ajb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:inbox-archive-outline" /></template>
