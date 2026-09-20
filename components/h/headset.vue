<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpd3_gbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mpd3_gbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:headset" /></template>
