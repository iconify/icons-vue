<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrl_9-k9t.css';
import '../../css/j/ja9psewjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hrl_9-k9t"/><path class="ja9psewjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:file-tray-full" /></template>
