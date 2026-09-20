<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc3bqvbgb.css';
import '../../css/i/i6107pbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc3bqvbgb"/><path class="i6107pbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-exclamation" /></template>
