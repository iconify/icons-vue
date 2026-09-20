<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqqivubyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqqivubyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:extension-off-filled" /></template>
