<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imk-gsbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imk-gsbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:emoji-normal-filled" /></template>
