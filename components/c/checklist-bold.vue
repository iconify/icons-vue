<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad56-ac1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad56-ac1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:checklist-bold" /></template>
