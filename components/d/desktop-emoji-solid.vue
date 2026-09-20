<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqrty5bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yqrty5bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:desktop-emoji-solid" /></template>
