<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw1oqzbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qw1oqzbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:chemical-hexagon-1-bold" /></template>
