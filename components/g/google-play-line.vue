<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btikh_bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btikh_bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:google-play-line" /></template>
