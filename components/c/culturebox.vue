<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl-rehbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl-rehbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:culturebox" /></template>
