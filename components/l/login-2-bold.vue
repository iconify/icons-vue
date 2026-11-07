<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo3g6abcw.css';
import '../../css/w/wvyu5ibqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fo3g6abcw"/><path class="wvyu5ibqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:login-2-bold" /></template>
