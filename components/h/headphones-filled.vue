<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do-6iuahm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do-6iuahm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:headphones-filled" /></template>
