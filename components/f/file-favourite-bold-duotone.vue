<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j59i-d3bj.css';
import '../../css/w/wzmgbfbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j59i-d3bj"/><path class="wzmgbfbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-favourite-bold-duotone" /></template>
