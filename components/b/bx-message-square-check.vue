<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk4qf0b7g.css';
import '../../css/r/rk3gvtbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk4qf0b7g"/><path class="rk3gvtbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-message-square-check" /></template>
