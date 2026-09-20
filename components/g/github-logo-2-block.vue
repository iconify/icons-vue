<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yct-3_m9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yct-3_m9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:github-logo-2-block" /></template>
