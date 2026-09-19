<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpd0sxoqw.css';
import '../../css/z/z-nr2n3tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpd0sxoqw"/><path class="z-nr2n3tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:gear-filled" /></template>
