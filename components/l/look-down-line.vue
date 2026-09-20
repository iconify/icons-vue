<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av0sy3bmo.css';
import '../../css/w/wli-clb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av0sy3bmo"/><path class="wli-clb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:look-down-line" /></template>
