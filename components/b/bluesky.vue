<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awnva-b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awnva-b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bluesky" /></template>
