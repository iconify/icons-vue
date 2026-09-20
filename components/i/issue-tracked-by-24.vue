<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaa3sjb5u.css';
import '../../css/t/t949fr4iy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uaa3sjb5u"/><path class="t949fr4iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:issue-tracked-by-24" /></template>
