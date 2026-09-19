<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq-xpubti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":799,"height":658};
const content = `<path class="bq-xpubti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:exchange" /></template>
