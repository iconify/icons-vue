<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc5iqbbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc5iqbbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-watch-stats" /></template>
