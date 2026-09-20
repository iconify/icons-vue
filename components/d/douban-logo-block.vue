<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixeqf5bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ixeqf5bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:douban-logo-block" /></template>
