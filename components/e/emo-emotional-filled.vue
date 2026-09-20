<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i53ry7bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i53ry7bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:emo-emotional-filled" /></template>
