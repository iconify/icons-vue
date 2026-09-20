<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0xjrdb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0xjrdb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:info-triangle-filled" /></template>
