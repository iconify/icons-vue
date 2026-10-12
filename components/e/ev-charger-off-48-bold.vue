<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxbfs7m-k.css';
import '../../css/m/m2anmnf8b.css';
import '../../css/d/d27j7obsk.css';
import '../../css/p/p34gu6lai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hxbfs7m-k"/><path class="m2anmnf8b"/><path class="d27j7obsk"/><path class="p34gu6lai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-charger-off-48-bold" /></template>
