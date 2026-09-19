<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voicgi8vf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voicgi8vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:connectivity" /></template>
