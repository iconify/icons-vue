<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lybrewbmj.css';
import '../../css/z/zp9omccou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lybrewbmj"/><path class="zp9omccou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-square-minimalistic-bold" /></template>
