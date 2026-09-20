<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzxv1fboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzxv1fboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-cnb" /></template>
