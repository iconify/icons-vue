<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcmvgqgbw.css';
import '../../css/s/sc6d7r8ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcmvgqgbw"/><path class="sc6d7r8ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:bookmark-minus-filled" /></template>
