<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aniu8tw4w.css';
import '../../css/c/cq-gv4s2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aniu8tw4w"/><path class="cq-gv4s2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-unknown-filled" /></template>
