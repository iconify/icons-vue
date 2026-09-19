<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am_-jxgiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="am_-jxgiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-cyrillic-small" /></template>
