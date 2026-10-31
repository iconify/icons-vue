<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr6eqdl_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr6eqdl_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:behance-round" /></template>
