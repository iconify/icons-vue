<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqijny-7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqijny-7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:direction-alt-line" /></template>
