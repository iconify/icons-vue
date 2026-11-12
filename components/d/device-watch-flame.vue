<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7p_66uvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7p_66uvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-watch-flame" /></template>
