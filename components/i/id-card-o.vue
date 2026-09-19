<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_0vdbc1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1536};
const content = `<path class="f_0vdbc1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:id-card-o" /></template>
