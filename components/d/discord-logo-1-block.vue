<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arr7c3bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="arr7c3bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:discord-logo-1-block" /></template>
