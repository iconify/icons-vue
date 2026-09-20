<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2aa21p0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2aa21p0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-d" /></template>
