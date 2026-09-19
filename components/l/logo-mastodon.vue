<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q84d4z_dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q84d4z_dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-mastodon" /></template>
