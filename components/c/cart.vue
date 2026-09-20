<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk67_kb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk67_kb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:cart" /></template>
