<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp7javlbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lp7javlbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:doc-text" /></template>
