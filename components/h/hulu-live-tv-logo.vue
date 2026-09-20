<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b05ho5hmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b05ho5hmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:hulu-live-tv-logo" /></template>
