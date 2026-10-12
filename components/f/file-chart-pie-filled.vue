<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqt8x36bs.css';
import '../../css/n/n7c3xab-f.css';
import '../../css/s/s2m1i3bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqt8x36bs"/><path class="n7c3xab-f"/><path class="s2m1i3bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-chart-pie-filled" /></template>
