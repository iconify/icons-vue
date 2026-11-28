<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbz91zb-u.css';
import '../../css/x/xai2kcsad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbz91zb-u secondary"/><path class="primary xai2kcsad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:filter-duo" /></template>
