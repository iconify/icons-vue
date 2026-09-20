<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkbg14b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xkbg14b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chair-solid" /></template>
