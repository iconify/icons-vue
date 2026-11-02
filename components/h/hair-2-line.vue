<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxbgdgbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxbgdgbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hair-2-line" /></template>
