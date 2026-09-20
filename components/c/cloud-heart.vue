<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctvcq8x9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctvcq8x9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-heart" /></template>
