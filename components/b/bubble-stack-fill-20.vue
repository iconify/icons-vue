<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzk3ruo3u.css';
import '../../css/y/ybw6xbfmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rzk3ruo3u"/><path class="ybw6xbfmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bubble-stack-fill-20" /></template>
