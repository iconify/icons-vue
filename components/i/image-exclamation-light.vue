<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skbbg-s7m.css';
import '../../css/x/xhvfopblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skbbg-s7m"/><path class="xhvfopblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-exclamation-light" /></template>
