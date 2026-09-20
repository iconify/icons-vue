<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbm9b0bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbm9b0bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-watch-up" /></template>
