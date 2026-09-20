<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stdec_j8d.css';
import '../../css/j/jryo535wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stdec_j8d"/><path class="jryo535wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:image-file-jpg-bold" /></template>
