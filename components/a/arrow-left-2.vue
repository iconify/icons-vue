<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe0cwd_yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe0cwd_yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-left-2" /></template>
