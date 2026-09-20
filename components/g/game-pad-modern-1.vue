<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z96yl-b9i.css';
import '../../css/a/ad7wyubda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z96yl-b9i"/><path clip-rule="evenodd" class="ad7wyubda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:game-pad-modern-1" /></template>
