<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrenmw-9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrenmw-9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:google-play-fill" /></template>
