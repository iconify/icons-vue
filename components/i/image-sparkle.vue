<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko66yhb_i.css';
import '../../css/u/uvq16eblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko66yhb_i"/><path class="uvq16eblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:image-sparkle" /></template>
