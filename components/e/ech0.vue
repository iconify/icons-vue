<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6iw_7bgc.css';
import '../../css/t/t2qw1ybvw.css';
import '../../css/o/o394wrbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="u6iw_7bgc"/><circle class="t2qw1ybvw"/><path class="o394wrbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ech0" /></template>
