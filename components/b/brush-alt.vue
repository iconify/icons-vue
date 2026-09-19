<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbw5lp6pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbw5lp6pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:brush-alt" /></template>
