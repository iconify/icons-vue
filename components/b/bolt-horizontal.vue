<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2ylsy7yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="w2ylsy7yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bolt-horizontal" /></template>
