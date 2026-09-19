<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_6rmtujx.css';
import '../../css/x/xmy0diffs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s_6rmtujx"/><path class="xmy0diffs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ipod" /></template>
