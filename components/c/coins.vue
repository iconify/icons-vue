<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lda6pabva.css';
import '../../css/t/ttouprbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lda6pabva"/><path class="ttouprbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:coins" /></template>
