<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko4fmo4iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ko4fmo4iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:cercle-6" /></template>
