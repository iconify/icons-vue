<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9xpoav3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9xpoav3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:broadcast-24" /></template>
