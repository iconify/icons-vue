<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko7evacid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko7evacid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:chevron-right" /></template>
