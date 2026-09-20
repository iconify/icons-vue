<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztdu4abng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztdu4abng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-tdesign" /></template>
