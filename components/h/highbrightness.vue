<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjk7w0bmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zjk7w0bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:highbrightness" /></template>
