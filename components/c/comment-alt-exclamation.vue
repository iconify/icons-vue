<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huymi8pfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huymi8pfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-alt-exclamation" /></template>
