<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0q0qobhx.css';
import '../../css/x/xoum1hbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a0q0qobhx"/><path class="xoum1hbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:listenbrainz" /></template>
