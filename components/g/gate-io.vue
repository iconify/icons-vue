<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3d7yhb3u.css';
import '../../css/m/m9_h30bse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3d7yhb3u"/><path class="m9_h30bse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gate-io" /></template>
