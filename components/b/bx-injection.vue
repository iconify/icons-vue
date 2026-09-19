<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx6yh-vht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx6yh-vht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-injection" /></template>
