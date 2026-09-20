<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2itiivcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2itiivcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:format-horizontal-align-top" /></template>
