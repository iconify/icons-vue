<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7r425_gi.css';
import '../../css/q/qgbgttb3i.css';
import '../../css/g/gtes6eb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7r425_gi"/><path class="qgbgttb3i"/><path class="gtes6eb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:feed-duotone" /></template>
