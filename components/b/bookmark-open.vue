<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzin90byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pzin90byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bookmark-open" /></template>
