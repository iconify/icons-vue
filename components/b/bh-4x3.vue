<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agv0_db3u.css';
import '../../css/s/s_kdtkgoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="agv0_db3u"/><path class="s_kdtkgoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:bh-4x3" /></template>
