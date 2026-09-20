<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9_yt-30p.css';
import '../../css/p/pexua2j3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s9_yt-30p"/><path clip-rule="evenodd" class="pexua2j3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bed-fill" /></template>
