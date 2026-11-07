<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc5eqrbuf.css';
import '../../css/l/ld5if1xzh.css';
import '../../css/o/o6imnm4pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc5eqrbuf"/><path class="ld5if1xzh"/><path class="o6imnm4pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hamburger-menu-outline" /></template>
