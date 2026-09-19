<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzkxdebtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzkxdebtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-vertical-distribute-center" /></template>
