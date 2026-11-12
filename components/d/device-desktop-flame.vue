<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anp7lrczn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anp7lrczn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-desktop-flame" /></template>
