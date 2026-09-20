<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyymwqb4g.css';
import '../../css/t/tpjkktbyw.css';
import '../../css/t/ti2ukbbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyymwqb4g"/><path class="tpjkktbyw"/><path class="ti2ukbbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:goal-24" /></template>
