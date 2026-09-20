<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/f/f5s6pk.css';
import '../../css/a/a-v8cn.css';
import '../../css/o/osy4ff.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c f5s6pk"/><path class="a-v8cn a0m25c"/><path class="a0m25c osy4ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:arrow-down-square" /></template>
