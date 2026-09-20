<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh-smq3-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zh-smq3-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:listenbrainz-light" /></template>
