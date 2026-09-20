<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baev--_qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="baev--_qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-right-down-circle-line" /></template>
