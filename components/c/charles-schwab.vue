<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckkr5xbvl.css';
import '../../css/z/zp5j1oj1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ckkr5xbvl"/><path class="zp5j1oj1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:charles-schwab" /></template>
