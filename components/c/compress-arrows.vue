<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiwv975yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiwv975yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:compress-arrows" /></template>
