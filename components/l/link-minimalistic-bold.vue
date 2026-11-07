<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu-jqnb_g.css';
import '../../css/j/j50599bqy.css';
import '../../css/y/ykm7xbcmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nu-jqnb_g"/><path class="j50599bqy"/><path class="ykm7xbcmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-minimalistic-bold" /></template>
