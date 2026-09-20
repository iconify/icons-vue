<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj-8hfbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yj-8hfbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bloglovin-logo-block" /></template>
