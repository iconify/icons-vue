<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in9lfx_ls.css';
import '../../css/w/wdn99oykn.css';
import '../../css/t/trzsg0bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="in9lfx_ls"/><path class="wdn99oykn"/><path class="trzsg0bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bazarr" /></template>
