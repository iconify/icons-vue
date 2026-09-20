<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xakau2eez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xakau2eez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:comment-fill-24" /></template>
