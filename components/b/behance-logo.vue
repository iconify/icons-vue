<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6e0w2b8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6e0w2b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:behance-logo" /></template>
