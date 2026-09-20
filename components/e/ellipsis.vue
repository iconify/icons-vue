<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-rluabaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-rluabaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ellipsis" /></template>
