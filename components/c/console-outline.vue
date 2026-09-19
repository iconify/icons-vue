<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg52a2w4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg52a2w4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:console-outline" /></template>
