<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiuo3xbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiuo3xbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-shrink" /></template>
