<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5lgt4bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5lgt4bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:audio-file-bold" /></template>
