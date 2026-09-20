<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9m3yhbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9m3yhbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:discussion-closed-24" /></template>
