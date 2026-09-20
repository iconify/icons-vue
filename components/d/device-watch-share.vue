<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw-gmiquk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw-gmiquk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-watch-share" /></template>
