<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s10jxb77c.css';
import '../../css/q/q0ne03bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s10jxb77c"/><path class="q0ne03bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:clh" /></template>
