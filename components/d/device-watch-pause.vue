<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er91nobum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er91nobum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-watch-pause" /></template>
